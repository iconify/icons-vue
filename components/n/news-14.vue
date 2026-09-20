<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqt2l-bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mqt2l-bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:news-14" /></template>
