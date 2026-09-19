<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erj9alb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="erj9alb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:slack" /></template>
