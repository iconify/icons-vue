<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epjs85bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="epjs85bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-spiral-stairs-round-down" /></template>
