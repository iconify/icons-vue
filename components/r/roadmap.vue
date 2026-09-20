<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfb6i5b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jfb6i5b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:roadmap" /></template>
