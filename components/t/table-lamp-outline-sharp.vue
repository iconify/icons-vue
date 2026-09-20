<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf9h2x3au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-lamp-outline-sharp" /></template>
<style>
.zf9h2x3au {
  fill: currentColor;
  d: path("M13 20.5v-1h7v1zM5.929 9.23h3.763V5H7.775zM16 17.73V6.578h-5.308v3.654H4.398L7.128 4h3.564v1.577H17v12.154zM5.929 9.23h3.763z");
}

</style>
