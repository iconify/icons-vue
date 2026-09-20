<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yak3gxrfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="yak3gxrfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-vertical-rotate-clockwise" /></template>
