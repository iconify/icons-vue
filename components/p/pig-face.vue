<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im10bsbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="im10bsbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pig-face" /></template>
