<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajkryueiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ajkryueiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:map-rtl" /></template>
