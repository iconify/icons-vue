<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikq2owb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ikq2owb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-alphabetically-outline" /></template>
