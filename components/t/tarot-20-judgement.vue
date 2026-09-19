<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_9wdobys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_9wdobys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-20-judgement" /></template>
