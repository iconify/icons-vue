<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":320};
const content = `<path class="modbayy2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pagekit" /></template>
<style>
.modbayy2a {
  fill: var(--svg-color--212121, #212121);
  d: path("M0 0v320h128v-48H48V45.333h160V224h-80v48h128V0z");
}

</style>
