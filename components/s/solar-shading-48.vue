<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv2p86eoi.css';
import '../../css/q/qfryzomdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tv2p86eoi"/><path class="qfryzomdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-shading-48" /></template>
