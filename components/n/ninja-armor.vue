<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlj03gb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nlj03gb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ninja-armor" /></template>
