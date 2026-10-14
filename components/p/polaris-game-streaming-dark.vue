<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8m4t8b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w8m4t8b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:polaris-game-streaming-dark" /></template>
