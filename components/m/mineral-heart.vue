<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq1k364qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vq1k364qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mineral-heart" /></template>
