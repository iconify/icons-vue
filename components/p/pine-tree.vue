<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xblgt7bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xblgt7bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pine-tree" /></template>
