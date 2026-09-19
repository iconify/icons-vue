<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kql266bwv.css';
import '../../css/y/yceptjbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kql266bwv"/><path class="yceptjbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:touch-interaction" /></template>
