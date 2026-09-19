<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1_-pnpef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1_-pnpef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:maze-cornea" /></template>
