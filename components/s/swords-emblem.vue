<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-ef07b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-ef07b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swords-emblem" /></template>
