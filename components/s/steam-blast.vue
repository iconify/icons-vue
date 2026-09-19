<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqo2l2bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kqo2l2bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:steam-blast" /></template>
