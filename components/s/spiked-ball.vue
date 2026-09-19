<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clbannbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="clbannbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiked-ball" /></template>
