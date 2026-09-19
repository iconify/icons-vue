<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpfd2sbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dpfd2sbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:slow-blob" /></template>
