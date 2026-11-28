<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3u6l-bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r3u6l-bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:stack-simple-check-bold" /></template>
