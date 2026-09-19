<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mro3w3b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mro3w3b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:uncertainty" /></template>
