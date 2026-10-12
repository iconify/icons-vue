<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di4565bwh.css';
import '../../css/w/w5e9b3z6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="di4565bwh"/><path class="w5e9b3z6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:monitor-stroke-20" /></template>
