<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s02ruwbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s02ruwbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-shekel" /></template>
