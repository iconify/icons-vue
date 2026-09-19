<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asgt9osdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="asgt9osdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pill" /></template>
