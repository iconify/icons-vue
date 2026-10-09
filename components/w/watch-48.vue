<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug38o3b8b.css';
import '../../css/p/p5wcu7plu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ug38o3b8b"/><path class="p5wcu7plu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:watch-48" /></template>
