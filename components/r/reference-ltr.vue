<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d74gefb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d74gefb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:reference-ltr" /></template>
