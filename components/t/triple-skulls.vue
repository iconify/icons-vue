<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9_-moegy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9_-moegy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triple-skulls" /></template>
