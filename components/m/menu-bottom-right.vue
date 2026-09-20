<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdk-bebxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="zdk-bebxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:menu-bottom-right" /></template>
