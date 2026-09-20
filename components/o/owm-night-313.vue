<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4t2ktbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="i4t2ktbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-313" /></template>
