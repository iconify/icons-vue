<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x0_7deb4j"/><path clip-rule="evenodd" class="nzcce5bkw"/><path class="rb_u9tdtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wow" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nzcce5bkw {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 19.875a7.875 7.875 0 1 0 0-15.75a7.875 7.875 0 0 0 0 15.75M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.rb_u9tdtf {
  fill: var(--svg-color--000, #000);
  d: path("M9.75 10.313c.622 0 1.126-.63 1.126-1.407c0-.776-.504-1.406-1.126-1.406c-.62 0-1.125.63-1.125 1.406c0 .777.504 1.406 1.125 1.406m4.5.001c.622 0 1.125-.63 1.125-1.407c0-.776-.503-1.406-1.125-1.406c-.621 0-1.124.63-1.124 1.406c0 .777.503 1.406 1.124 1.406M12 18.188c1.554 0 2.813-1.511 2.813-3.375s-1.26-3.376-2.812-3.376c-1.554 0-2.813 1.512-2.813 3.376s1.26 3.374 2.813 3.374");
}

.x0_7deb4j {
  fill: var(--svg-color--f3ba2f, #f3ba2f);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

</style>
