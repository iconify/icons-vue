<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hykr4xmaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hykr4xmaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:review-response-solid" /></template>
