<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqnnz1b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqnnz1b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tattered-banner" /></template>
