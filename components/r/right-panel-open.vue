<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-3s-3ndv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n-3s-3ndv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:right-panel-open" /></template>
