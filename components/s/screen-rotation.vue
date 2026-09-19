<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpga2ccyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dpga2ccyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:screen-rotation" /></template>
