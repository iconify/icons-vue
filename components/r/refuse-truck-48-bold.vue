<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxrct6bvh.css';
import '../../css/p/pkxeyyb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nxrct6bvh"/><path class="pkxeyyb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refuse-truck-48-bold" /></template>
