<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6s1d5urq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="d6s1d5urq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waxing-gibbous-1" /></template>
