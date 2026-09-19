<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj2mv2b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xj2mv2b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-recycling" /></template>
