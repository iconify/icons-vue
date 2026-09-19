<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t57rj1bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t57rj1bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:medieval-gate" /></template>
