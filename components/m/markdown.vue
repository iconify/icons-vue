<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twl58k00n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="twl58k00n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:markdown" /></template>
