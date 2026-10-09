<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/modu3zppg.css';
import '../../css/i/i-3hvmfaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="modu3zppg"/><path class="i-3hvmfaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:move-horizontal-48" /></template>
