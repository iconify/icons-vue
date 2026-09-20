<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o205f_btu"/><path class="vlfltdbow"/><path class="g_2zs9bjv"/><path class="j4wowdbnr"/><path class="toi8swi8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:repeat-button" /></template>
<style>
.g_2zs9bjv {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.j4wowdbnr {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M83.6 64a3.996 3.996 0 0 1-5.64-.44c-.61-.71-.95-1.62-.96-2.56V47c0-1.1-.9-2-2-2H41c-4.8 0-11.5 1.5-12 12L14.2 70.3A36 36 0 0 1 13 61c0-17.7 12.5-32 28-32h34c1.1 0 2-.9 2-2V13a4 4 0 0 1 6.6-3l24 24a3.994 3.994 0 0 1 .35 5.65c-.11.13-.23.24-.35.35z");
}

.o205f_btu {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.toi8swi8h {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M38.4 58a3.996 3.996 0 0 1 5.64.44c.61.71.95 1.62.96 2.56v14c0 1.1.9 2 2 2h34c4.8 0 11.6-1.5 12-12l14.8-13.3c.81 3.03 1.21 6.16 1.2 9.3c0 17.7-12.5 32-28 32H47c-1.1 0-2 .9-2 2v14a4 4 0 0 1-6.6 3l-24-24a3.994 3.994 0 0 1 0-6z");
}

.vlfltdbow {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
