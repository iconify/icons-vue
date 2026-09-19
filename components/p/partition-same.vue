<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w79t2kb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w79t2kb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:partition-same" /></template>
