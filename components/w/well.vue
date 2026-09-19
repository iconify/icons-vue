<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8rkqh9yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l8rkqh9yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:well" /></template>
