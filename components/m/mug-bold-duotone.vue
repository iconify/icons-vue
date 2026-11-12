<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="cf4va2ows"/><path class="ldse3ccpn"/></g><path clip-rule="evenodd" class="e854pc0lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mug-bold-duotone" /></template>
<style>
.cf4va2ows {
  d: path("M22 20.25C22.4142 20.25 22.75 20.5858 22.75 21C22.75 21.4142 22.4142 21.75 22 21.75H2C1.58579 21.75 1.25 21.4142 1.25 21C1.25 20.5858 1.58579 20.25 2 20.25H22Z");
}

.e854pc0lb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.00174 13C3 12.6878 3 12.355 3 12V7C3 5.11438 3 4.17157 3.58579 3.58579C4.17157 3 5.11438 3 7 3H13C14.8856 3 15.8284 3 16.4142 3.58579C16.649 3.82059 16.7897 4.11275 16.874 4.5H18C20.5261 4.5 22.75 6.31185 22.75 8.75C22.75 11.1882 20.5261 13 18 13H3.00174ZM16.9957 6C17 6.30037 17 6.63226 17 7V11.5H18C19.8921 11.5 21.25 10.1778 21.25 8.75C21.25 7.32216 19.8921 6 18 6H16.9957Z");
}

.ldse3ccpn {
  d: path("M16.998 13C16.9859 15.175 16.8895 16.3527 16.1211 17.1211C15.2424 17.9997 13.8283 18 11 18H9C6.17172 18 4.75756 17.9998 3.87891 17.1211C3.11062 16.3527 3.01406 15.1749 3.00195 13H16.998Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
