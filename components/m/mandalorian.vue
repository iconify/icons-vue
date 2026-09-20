<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l472vy-ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l472vy-ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mandalorian" /></template>
