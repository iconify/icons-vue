<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es0g2ybga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="es0g2ybga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:umbrella" /></template>
