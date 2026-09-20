<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o205f_btu"/><path class="vlfltdbow"/><path class="uz0y3go5q"/><path class="ilpf20j4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:play-or-pause-button" /></template>
<style>
.ilpf20j4o {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M82.1 92H71.9a1.9 1.9 0 0 1-1.9-1.9V37.9c0-1.05.85-1.9 1.9-1.9h10.3c1.05 0 1.9.85 1.9 1.9v52.3c-.1 1.03-.97 1.81-2 1.8m22 0H93.9a1.9 1.9 0 0 1-1.9-1.9V37.9c0-1.05.85-1.9 1.9-1.9h10.3c1.05 0 1.9.85 1.9 1.9v52.3c-.1 1.03-.97 1.81-2 1.8M18 64V38.3a2.258 2.258 0 0 1 3.4-2L64.8 62c1.13.72 1.47 2.22.75 3.35c-.19.3-.45.55-.75.75L21.4 91.7c-1.08.63-2.46.27-3.09-.81c-.21-.36-.32-.77-.31-1.19z");
}

.o205f_btu {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.uz0y3go5q {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-12.438 2.455-14.738 5.255s-3.212 5.549-3.312 12.349c0 4.8.304 9.3 2.5 9.3c2.436 0 5.462-7.386 8.262-11.786C27.012 16.618 39.7 15.9 39.7 12.9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vlfltdbow {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
