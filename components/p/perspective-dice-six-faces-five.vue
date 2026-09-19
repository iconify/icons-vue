<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcjo14bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gcjo14bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-six-faces-five" /></template>
