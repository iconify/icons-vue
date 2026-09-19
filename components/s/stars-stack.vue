<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afj6p5bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="afj6p5bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stars-stack" /></template>
