<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7nmgfboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m7nmgfboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:striking-clamps" /></template>
