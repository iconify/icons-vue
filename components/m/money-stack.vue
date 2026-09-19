<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khm5-lbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="khm5-lbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:money-stack" /></template>
