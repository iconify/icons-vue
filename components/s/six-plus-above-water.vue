<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i03w9cvef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i03w9cvef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:six-plus-above-water" /></template>
