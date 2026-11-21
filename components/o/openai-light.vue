<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh3ngdcch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":354.674,"height":354.674,"left":180.5,"top":180.5};
const content = `<path class="oh3ngdcch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openai-light" /></template>
