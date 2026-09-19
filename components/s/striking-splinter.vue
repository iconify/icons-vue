<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p08cwsb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p08cwsb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:striking-splinter" /></template>
