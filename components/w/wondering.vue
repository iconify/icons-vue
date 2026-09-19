<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t82-wgb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t82-wgb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:wondering" /></template>
