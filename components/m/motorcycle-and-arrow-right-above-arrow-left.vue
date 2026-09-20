<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u65_98btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u65_98btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-arrow-right-above-arrow-left" /></template>
