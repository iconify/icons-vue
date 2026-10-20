<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnqzr1ypb.css';
import '../../css/j/jo6iw5bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pnqzr1ypb"/><path class="jo6iw5bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:search-sparkle-20-bold" /></template>
