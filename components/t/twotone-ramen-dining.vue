<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfad1cc7w"/><path class="ug0mau54l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-ramen-dining" /></template>
<style>
.hfad1cc7w {
  fill: currentColor;
  d: path("m8.73 18.39l1.27.5V20h4v-1.11l1.27-.5c2.16-.85 3.74-2.47 4.4-4.39H4.34c.65 1.92 2.24 3.54 4.39 4.39");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ug0mau54l {
  fill: currentColor;
  d: path("M22 3.51V2L4 3.99V12H2c0 3.69 2.47 6.86 6 8.25V22h8v-1.75c3.53-1.39 6-4.56 6-8.25H10.5V8H22V6.5H10.5V4.78zM8 5.06l1-.11V6.5H8zM8 8h1v4H8zM5.5 5.34l1-.11V6.5h-1zM5.5 8h1v4h-1zm14.16 6c-.66 1.92-2.24 3.54-4.4 4.39l-1.26.5V20h-4v-1.11l-1.27-.5c-2.16-.85-3.74-2.47-4.4-4.39z");
}

</style>
