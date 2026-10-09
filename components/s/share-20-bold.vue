<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9rholkuw.css';
import '../../css/z/zr6v3gbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p9rholkuw"/><path class="zr6v3gbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:share-20-bold" /></template>
