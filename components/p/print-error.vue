<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv3vvabhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-error" /></template>
<style>
.kv3vvabhc {
  fill: currentColor;
  d: path("M7 20v-4H3.577v-5.384q0-.85.577-1.425t1.423-.576h12.846q.558 0 1.013.275q.455.274.697.726H17.73q-.667 0-1.141.474t-.475 1.14v3.232H8V19h8.116v1zM7 7.846v-3.23h10v3.23zM18.48 19.79q-.21-.21-.21-.52t.21-.521q.209-.21.52-.21t.52.21t.21.52t-.21.52Q19.312 20 19 20t-.52-.21m.02-4.02v-4h1v4z");
}

</style>
