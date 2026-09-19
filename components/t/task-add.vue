<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf9u9jrxa.css';
import '../../css/u/uz2w82b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kf9u9jrxa"/><path class="uz2w82b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-add" /></template>
