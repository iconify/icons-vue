<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es4p5rbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="es4p5rbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:necklace" /></template>
