<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9zba1bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e9zba1bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shepherds-crook" /></template>
