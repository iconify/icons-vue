<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm6t7ttvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bm6t7ttvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pummeled" /></template>
