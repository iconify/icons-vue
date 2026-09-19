<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-of5g6ba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-of5g6ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-09-the-hermit" /></template>
