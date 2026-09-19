<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t3xbim0bo"/><path class="kuypn8boz"/><path class="wnogkjbrf"/><path class="wrhznrb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:tongue" /></template>
<style>
.kuypn8boz {
  fill: var(--svg-color--f45ba1, #f45ba1);
  d: path("M49.05 51.747C49.05 58.517 41.415 64 32 64c-9.412 0-17.05-5.483-17.05-12.253l3.676-16.17c0-6.763 3.959-10.205 13.371-10.205c9.414 0 13.373 3.442 13.373 10.205l3.676 16.17");
}

.t3xbim0bo {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M63.66 19.657c0 17.481-14.178 31.661-31.661 31.661c-17.473 0-31.658-14.18-31.658-31.661");
}

.wnogkjbrf {
  fill: var(--svg-color--db5397, #db5397);
  d: path("M32.931 60.1c0 .221-.417.4-.931.4s-.931-.18-.931-.4V29.265c0-.224.417-.403.931-.403s.931.179.931.403z");
}

.wrhznrb0r {
  fill: var(--svg-color--fff, #fff);
  d: path("M58.23 22.84c0 6.979-11.989 12.648-26.768 12.648c-14.771 0-26.76-5.669-26.76-12.648");
}

</style>
