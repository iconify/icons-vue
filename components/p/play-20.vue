<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srqezcbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="srqezcbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:play-20" /></template>
