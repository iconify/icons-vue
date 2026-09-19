<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq8ap1beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uq8ap1beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rolling-suitcase" /></template>
