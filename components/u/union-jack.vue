<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek-sb1riu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ek-sb1riu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:union-jack" /></template>
