<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnq6dbbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wnq6dbbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-align-right" /></template>
