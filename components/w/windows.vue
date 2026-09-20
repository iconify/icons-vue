<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrts1unsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":88,"height":88};
const content = `<path class="yrts1unsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:windows" /></template>
