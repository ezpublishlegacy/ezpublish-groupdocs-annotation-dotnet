##GroupDocs.Annotation for .NET – ezPublish Add-on

GroupDocs.Annotation for .NET is a lightweight library that enables end users to annotate common document and image types online using only a web-browser. With this add-on, ezPublish developers and site owners can easily integrate GroupDocs.Annotation for .NET into their websites.

The library provides you with a web-based UI that can be embedded to a web page as an annotation widget. Using the widget, end users can upload images and documents for online review and annotation, all directly on your ezPublish website.

Supported file types include: PDF and Microsoft Word documents, Excel spreadsheets, PowerPoint presentations, Visio diagrams, CAD drawings, raster images (TIFF, JPEG, PNG, BMP, GIF) and many more.

###Features at a Glance

- **Cross-platform compatibility.** End users can annotate documents and images using any standard web-browser, including IE8+, Chrome, Safari5+ and Mozilla FireFox. There is no need to install any software or browser plugin.
- **Comprehensive set of annotation tools:** rectangle, polyline, sticky notes, arrow, watermarks, redaction, text underline/strikethrough, etc.
- **Real-time annotation mode.** Multiple users can annotate the same document simultaneously, each being able to see and reply to others’ comments in real time.
- **Native Microsoft Word & PDF annotations.** PDF and Microsoft Word documents annotated using GroupDocs.Annotation for .NET on your website can be saved along with added annotations for further offline review and editing.

For more details on GroupDocs.Annotation for .NET, please visit its homepage at:
[http://groupdocs.com/dot-net/document-annotation-library](http://groupdocs.com/dot-net/document-annotation-library) 

___

###Add-on Installation:

Please note that this add-on integrates the downloadable .NET version of GroupDocs.Annotation, which can be deployed on-premises. We also offer a [Java library]( https://github.com/groupdocs/ezpublish-groupdocs-annotation-java) for on-premises deployment and a [cloud-based integration](https://github.com/groupdocs/ez-groupdocs-annotation).

Also, please be aware that GroupDocs.Annotation for .NET is a commercial library, but you can test it with a free evaluation.

1. Unzip the **groupdocsAnnotationNet** package to the **groupdocsAnnotation** folder within the **extensions** directory of your ezPublish site. 
2. Open the **site/settings/override/site.ini.append.php** file and add **ActiveExtensions[]=groupdocsAnnotationNet** under **[ExtensionSettings]**.
3. Go to: **Admin** > **Setup** > **Extensions** and check the **groupdocsAnnotation** checkbox.
4. Go to: **Setup** > **Extensions** and press the **Regenerate auto loaded arrays for extensions** in the bottom of the page.
5. Go to: **User Accounts** > **Roles and policies** > **Anonymous** then click **Edit Role**.
6. If **groupdocsAnnotationNet** is not listed there, press **New Policy** > choose **Module: groupdocsAnnotationNet** > **Grant access to all functions** > **Save**.
6. Go to **Setup** and press **Clear all caches**.

___

###Useful Links

GroupDocs.Annotation for .NET Library - Product Home:   
[http://groupdocs.com/dot-net/document-annotation-library](http://groupdocs.com/dot-net/document-annotation-library) 

GroupDocs.Annotation for .NET on the ezPublish Marketplace:   
[http://projects.ez.no/groupdocs_annotation_for_dot_net](http://projects.ez.no/groupdocs_annotation_for_dot_net)
