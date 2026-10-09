<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u48dvzb0i.css';
import '../../css/j/j9cnkbbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u48dvzb0i"/><path class="j9cnkbbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wheelchair-20" /></template>
