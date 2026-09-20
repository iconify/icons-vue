<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="izjs16bix"/><path class="hg--kzb0u"/><path class="eh-vg4bvf"/><path class="ojxgj-2fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:right-arrow-curving-up" /></template>
<style>
.eh-vg4bvf {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M35.16 79.96c1.74.02 3.26 1.15 3.8 2.8c1.7 5.2 8.1 9.2 15.5 9.2c8.7 0 16-5.5 16-12v-34c0-1.1-.9-2-2-2h-14a4 4 0 0 1-3-6.6l24-24a3.994 3.994 0 0 1 6 0l24 24a3.996 3.996 0 0 1-.44 5.64c-.71.61-1.62.95-2.56.96h-14c-1.1 0-2 .9-2 2v34c0 15.5-14.3 28-32 28c-15.8 0-29-10.1-31.5-23.3a3.996 3.996 0 0 1 3.9-4.7z");
}

.hg--kzb0u {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M110.16 3.96h-98.2a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.46c.09-4.05-3.13-7.41-7.18-7.5z");
}

.izjs16bix {
  fill: var(--svg-color--427687, #427687);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.ojxgj-2fp {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M40.16 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
