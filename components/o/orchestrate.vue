<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k50d2ackq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k50d2ackq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:orchestrate" /></template>
