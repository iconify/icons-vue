<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsikqpeid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsikqpeid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:woman-elf-face" /></template>
