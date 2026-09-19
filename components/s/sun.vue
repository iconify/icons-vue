<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my_j7-_xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="my_j7-_xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sun" /></template>
