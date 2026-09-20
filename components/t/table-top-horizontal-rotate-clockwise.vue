<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueos75g2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ueos75g2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-horizontal-rotate-clockwise" /></template>
