<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhf7l7mgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stop-outline-sharp" /></template>
<style>
.rhf7l7mgl {
  fill: currentColor;
  d: path("M8 8v8zM6 18V6h12v12zm2-2h8V8H8z");
}

</style>
