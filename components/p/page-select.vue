<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcxsgkb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xcxsgkb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:page-select" /></template>
