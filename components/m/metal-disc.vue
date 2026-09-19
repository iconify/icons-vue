<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly5l7q92e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ly5l7q92e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:metal-disc" /></template>
