<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg_2tebxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cg_2tebxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiked-armor" /></template>
