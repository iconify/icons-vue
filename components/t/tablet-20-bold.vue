<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byse_4bgl.css';
import '../../css/j/j17_kebzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="byse_4bgl"/><path class="j17_kebzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tablet-20-bold" /></template>
