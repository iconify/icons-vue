<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynvpeikbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynvpeikbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:octagram-shape-flat" /></template>
