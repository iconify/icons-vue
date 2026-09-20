<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjdc6p5hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rjdc6p5hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-descending-above-water" /></template>
