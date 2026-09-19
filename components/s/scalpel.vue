<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2-9473u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ij2-9473u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scalpel" /></template>
