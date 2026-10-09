<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvggvrfgt.css';
import '../../css/x/x3yktye3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kvggvrfgt"/><path class="x3yktye3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-grid-20-bold" /></template>
