<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imrkppwci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imrkppwci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-18-the-moon" /></template>
