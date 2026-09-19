<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bfv891ddc"/><circle class="d4s8ejvev"/><circle class="k_kv20_2j"/><path class="ux_lc7k-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:worried-face" /></template>
<style>
.bfv891ddc {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30c16.571 0 30.002-13.432 30.002-30S48.57 2 32 2m0 57.5C16.836 59.5 4.5 47.164 4.5 32S16.836 4.5 32 4.5S59.502 16.836 59.502 32S47.164 59.5 32 59.5");
}

.d4s8ejvev {
  cx: 20.5px;
  cy: 29.59px;
  r: 5px;
  fill: currentColor;
}

.k_kv20_2j {
  cx: 43.502px;
  cy: 29.59px;
  r: 5px;
  fill: currentColor;
}

.ux_lc7k-h {
  fill: currentColor;
  d: path("M52.619 17.051a16.42 16.42 0 0 0-13.492-3.615c-.703.135-.193 2.27.385 2.156c4.17-.748 8.457.4 11.693 3.133c.443.386 1.955-1.205 1.414-1.674m-28.131-1.61c.578.113 1.09-2.021.387-2.156A16.43 16.43 0 0 0 11.383 16.9c-.541.469.969 2.063 1.412 1.674a14.24 14.24 0 0 1 11.693-3.133m16.094 28.987c-5.404-2.538-11.788-2.54-17.197-.012c-1.339.645.329 4.15 1.662 3.5c3.571-1.665 8.896-2.306 13.875.01c1.334.619 3.078-2.813 1.66-3.498");
}

</style>
