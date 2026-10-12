<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urcr4j1xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="urcr4j1xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pause-fill-20" /></template>
