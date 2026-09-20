<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7k-s0i3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="c7k-s0i3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moonset" /></template>
