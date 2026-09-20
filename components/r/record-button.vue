<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c_5tmtm1a"/><path class="ydmhzfbpu"/><circle class="e92cq_b9i"/><path class="srhevqbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:record-button" /></template>
<style>
.c_5tmtm1a {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 3.96H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.e92cq_b9i {
  cx: 60.551px;
  cy: 61.41px;
  r: 28px;
  fill: var(--svg-color--fafafa, #fafafa);
}

.srhevqbyi {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ydmhzfbpu {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 3.96H11.5a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.46c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
