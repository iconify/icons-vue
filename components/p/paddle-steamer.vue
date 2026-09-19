<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdwvp9b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdwvp9b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paddle-steamer" /></template>
