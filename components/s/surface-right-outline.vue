<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o59d3w3ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o59d3w3ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:surface-right-outline" /></template>
