<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij8es8bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ij8es8bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ring-mould" /></template>
