<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa9xombwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa9xombwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-spade" /></template>
