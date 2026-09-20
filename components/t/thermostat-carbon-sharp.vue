<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7udfjbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thermostat-carbon-sharp" /></template>
<style>
.k7udfjbos {
  fill: currentColor;
  d: path("M12 22.8L1.2 12L12 1.2L22.8 12z");
}

</style>
