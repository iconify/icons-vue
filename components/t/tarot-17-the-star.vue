<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvnsribyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvnsribyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-17-the-star" /></template>
