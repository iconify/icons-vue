<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trf3a5mss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trf3a5mss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:select" /></template>
