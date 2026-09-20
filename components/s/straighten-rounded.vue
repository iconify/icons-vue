<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p18ycs30f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:straighten-rounded" /></template>
<style>
.p18ycs30f {
  fill: currentColor;
  d: path("M4.616 17q-.691 0-1.153-.462T3 15.378V8.622q0-.697.463-1.16T4.615 7H7.5v3.73q0 .213.144.357t.357.144t.356-.144t.143-.356V7h3v3.73q0 .213.144.357t.357.144t.356-.144t.143-.356V7h3v3.73q0 .213.144.357t.357.144t.356-.144t.143-.356V7h2.885q.69 0 1.152.463T21 8.622v6.756q0 .697-.463 1.16T19.385 17z");
}

</style>
