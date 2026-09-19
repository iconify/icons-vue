<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8a2d4biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8a2d4biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-07-the-chariot" /></template>
