<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llwprqmox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="llwprqmox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tuba" /></template>
