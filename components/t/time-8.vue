<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ear-7c2pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ear-7c2pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-8" /></template>
