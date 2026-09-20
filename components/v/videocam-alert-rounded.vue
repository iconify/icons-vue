<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aropydz2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-alert-rounded" /></template>
<style>
.aropydz2g {
  fill: currentColor;
  d: path("M12.698 19q-.332 0-.509-.267t-.047-.595q.174-.49.26-1.018t.087-1.068q0-2.67-1.875-4.543T6.071 9.635q-.438 0-.877.055q-.438.054-.852.189q-.326.085-.594-.082q-.267-.166-.267-.493V6.616q0-.691.462-1.153T5.096 5h10.77q.69 0 1.152.463t.463 1.153v4.653l2.342-2.342q.193-.192.444-.096q.252.096.252.369v5.6q0 .273-.252.37q-.251.095-.444-.097l-2.342-2.342v4.654q0 .69-.463 1.153T15.866 19zm-9.533-.164Q2 17.67 2 16t1.165-2.835T6 12t2.836 1.165T10 16t-1.164 2.836T6 20t-2.835-1.164M6 16.577q.162 0 .273-.111q.112-.112.112-.274v-2.23q0-.162-.112-.273T6 13.577t-.273.112t-.111.273v2.23q0 .162.111.274q.112.111.273.111m0 1.846q.2 0 .33-.13t.132-.331t-.131-.331T6 17.5t-.33.13t-.132.332t.131.33t.331.131");
}

</style>
