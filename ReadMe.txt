#1. <meta charset="utf-8"> 
// is used for bangla font default

<style>

.page-header, .page-header-space {
    height: 50px;
  }
  
  .page-footer, .page-footer-space {
    height: 50px;
  
  }
  
  .page-footer {
    display: flex;
    align-items: center;
    justify-content: center;
    position: fixed;
    bottom: 0;
    width: 100%;
    border-top: 1px solid black; /* for demo */
    /* background: yellow; for demo */
  }
  
  .page-header {
    display: flex;
    align-items: center;
    justify-content: center;
    position: fixed;
    top: 0mm;
    width: 100%;
    border-bottom: 1px solid black; /* for demo */
    /* background: yellow; for demo */
  }

  @media print {
    *,html,body{
        font-family: nikosh !important; 
        font-size: 16pt;
    }
    
  }

</style>

<div class="page-header">
    I'm The Header
    <br/>
  </div>

  <div class="page-footer">
    I'm The Footer
  </div>

  <table style="margin: auto;">

    <thead>
      <tr>
        <td>
          <!--place holder for the fixed-position header-->
          <div class="page-header-space"></div>
        </td>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td>
          <!--*** CONTENT GOES HERE ***-->

        </td>
    </tr>
    </tbody>
      
        <tfoot>
        <tr>
            <td>
            <!--place holder for the fixed-position footer-->
            <div class="page-footer-space"></div>
            </td>
        </tr>
        </tfoot>
    
    </table>