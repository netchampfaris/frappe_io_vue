<template>
  <footer class="border-top bg-dark pt-4">
    <div class="container">
      <div class="row mt-4">
        <div class='col-sm-12 col-md-6' style='display: flex; flex-direction: column; justify-content: space-between;'>
          <img class="brand-logo" src="/img/frappe-logo-white.svg">
          <div class="text-muted">
            <p style="line-height: 2">
              &copy;
              <span id="year"></span> Frappe Technologies Pvt. Ltd.
              <br>Content licensed under
              <a href="https://creativecommons.org/licenses/by-sa/3.0/" class="text-muted underline" target="_blank">
                CC-BY-SA 3.0</a>.
              <br>Read the
              <a href="https://erpnext.com/terms" class="text-muted underline">terms of use</a>.
            </p>
          </div>
        </div>
        <div class="col-xs-12 col-sm-6 col-md-3">
          <h6 class='text-light'>Social</h6>
          <ul class="list-unstyled">
            <li class="py-2">
              <a href="https://frappe.io/blog" class="text-muted">Blog</a>
            </li>
            <li class="py-2">
              <a href="https://discuss.erpnext.com" class="text-muted">Forum</a>
            </li>
            <li class="py-2">
              <a href="https://github.com/frappe" class="text-muted">GitHub</a>
            </li>
            <li class="py-2">
              <a href="https://twitter.com/erpnext" class="text-muted">Twitter</a>
            </li>
            <li class="py-2">
              <a href="https://medium.com/frapp%C3%A9-thoughts" class="text-muted">Medium</a>
            </li>
            <li class="py-2">
              <a href="https://www.facebook.com/ERPNext" class="text-muted">Facebook</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-12 col-sm-6 col-md-3">
          <h6 class='text-light'>Company</h6>
          <ul class="list-unstyled">
            <li class="py-2">
              <a href="https://erpnext.com" class="text-muted">ERPNext</a>
            </li>
            <li class="py-2">
              <a href="https://frappe.io/about" class="text-muted">Team</a>
            </li>
            <li class="py-2">
              <a href="https://frappe.io/about" class="text-muted">Jobs</a>
            </li>
            <li class="py-2">
              <a href="https://frappe.io/about#contact" class="text-muted">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
.brand-logo {
  height: 3rem;
  width: 3rem;
}
</style>
