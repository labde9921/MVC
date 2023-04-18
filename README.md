# MVC
using System;
using System.Collections.Generic;
using System.Linq;
using System.Web;
using System.Web.Mvc;
using System.Web.UI.WebControls;

namespace MVCActionResult.Controllers
{
    public class HomeController : Controller
    {
        public ViewResult Index()
        {
            return View();
        }

        public ViewResult Register() 
        {
            return View();
        }

        public ViewResult Login()
        {
            return View();
        }


    }
}
