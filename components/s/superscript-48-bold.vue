<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi9ey6-_v.css';
import '../../css/d/ddxiy4bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vi9ey6-_v"/><path class="ddxiy4bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:superscript-48-bold" /></template>
