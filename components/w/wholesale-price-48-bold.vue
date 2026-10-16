<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5t0sbxt.css';
import '../../css/m/m29p03crh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zw5t0sbxt"/><path class="m29p03crh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wholesale-price-48-bold" /></template>
