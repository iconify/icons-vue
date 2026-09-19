<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru4mugble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ru4mugble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:medal" /></template>
