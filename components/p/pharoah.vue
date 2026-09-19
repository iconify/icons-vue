<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og9s0rb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="og9s0rb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pharoah" /></template>
