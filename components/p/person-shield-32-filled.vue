<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j-9enuroq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-shield-32-filled" /></template>
<style>
.j-9enuroq {
  fill: currentColor;
  d: path("M22.293 15.766c.376-.354 1.038-.354 1.414 0c.943.887 2.755 2.298 4.982 2.588c.445.057.811.389.811.803v3.87c0 5.204-5.17 7.093-6.288 7.44a.7.7 0 0 1-.423 0c-1.118-.347-6.288-2.236-6.288-7.44l-.001-3.87c0-.414.366-.746.81-.803c2.228-.29 4.04-1.7 4.983-2.588M15.324 18a2.1 2.1 0 0 0-.311.905l-.013.252l.001 3.87l.004.295c.095 3.015 1.65 5.088 3.273 6.41l.137.107c-.782.105-1.59.161-2.415.161c-3.198 0-6.141-.823-8.315-2.207C5.523 26.417 4 24.393 4 22v-.5A3.5 3.5 0 0 1 7.5 18zM16 2a7 7 0 1 1 0 14a7 7 0 0 1 0-14");
}

</style>
