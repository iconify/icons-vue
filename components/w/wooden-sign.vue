<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipir0_b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipir0_b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wooden-sign" /></template>
