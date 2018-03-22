using System;
using System.Collections.Generic;
using System.ComponentModel.DataAnnotations;
using System.Linq;
using System.Web;

namespace AssessmentHospital.Models
{
    public class RegisterClass
    {

        public int pid { get; set; }

        [Required(ErrorMessage = "Enter Patient's Name")]
        [Display(Name = "Patient Name:")]
        public string name { get; set; }

        [Required(ErrorMessage = "Enter Patient's Age")]
        [Display(Name = "Age:")]
        public int age { get; set; }

        [Required(ErrorMessage = "Enter Patient's Contact Number")]
        [RegularExpression(@"[0-9]{10}", ErrorMessage = "Enter 10 digit valid mobile number")]
        [Display(Name = "Contact Number:")]
        public long contact { get; set; }

        [Required(ErrorMessage = "Enter Patient's Address")]
        [Display(Name = "Address:")]
        public string adr { get; set; }
    }

    [MetadataType(typeof(RegisterClass))]
    public partial class tblPatient1349205
    {
    }
}
