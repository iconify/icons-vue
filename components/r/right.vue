<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvn6qn9gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rvn6qn9gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:right" /></template>
