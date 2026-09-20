<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":257};
const content = `<path class="t40wl4brg"/><path class="ouml2kb5y"/><path class="vyx56etgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:modulus" /></template>
<style>
.ouml2kb5y {
  d: path("M.08 161.203l46.312-29.412L.08 108.636v52.567");
  fill: var(--svg-color--e55425, #E55425);
}

.t40wl4brg {
  d: path("M125.287 82.052L.08.58v255.561h46.312v-68.606l78.895-49.742l80.615-50.595v168.943h49.739V.581L125.287 82.051");
  fill: var(--svg-color--c7c8c9, #C7C8C9);
}

.vyx56etgs {
  d: path("M125.287 82.052l-78.895 49.739v55.744l78.895-49.742v-55.74");
  fill: var(--svg-color--40403e, #40403E);
}

</style>
