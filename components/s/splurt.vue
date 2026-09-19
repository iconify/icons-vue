<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vibod_97g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vibod_97g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:splurt" /></template>
