=================================================
     Ext.NET 2.2.0 Successfully Installed!
=================================================

To view a sample:

1. hit F5
2. browse to /Ext.NET.Default.aspx


More samples available at http://examples.ext.net/

Technical support available at http://forums.ext.net/

An Ext.NET Pro license can be purchased at http://ext.net/store/


=================================================
               TROUBLESHOOTING
=================================================

1.  If Ext.NET was previously installed in this Project, you might need to add
    the following <runtime> node to your root Web.config:

<?xml version="1.0"?>
<configuration>
  <runtime>
    <assemblyBinding xmlns="urn:schemas-microsoft-com:asm.v1">
      <dependentAssembly>
        <assemblyIdentity name="Newtonsoft.Json" publicKeyToken="30ad4fe6b2a6aeed" />
        <bindingRedirect oldVersion="1.0.0.0-4.5.10" newVersion="4.5.11" />
      </dependentAssembly>
      <dependentAssembly>
        <assemblyIdentity name="Ext.Net.Utilities" publicKeyToken="2c34ac34702a3c23" />
        <bindingRedirect oldVersion="0.0.0.0-2.2.0" newVersion="2.2.1" />
      </dependentAssembly>
      <dependentAssembly>
        <assemblyIdentity name="Transformer.NET" publicKeyToken="e274d618e7c603a7" />
        <bindingRedirect oldVersion="0.0.0.0-2.1.0" newVersion="2.1.1" />
      </dependentAssembly>
    </assemblyBinding>
  </runtime>
</configuration>

For further information, a Sample.Web.config has been added to the /App_Readme/Ext.NET/ folder of this project.