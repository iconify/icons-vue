<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp069p2og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp069p2og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sugar-cane" /></template>
