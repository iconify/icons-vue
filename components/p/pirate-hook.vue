<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrta7ubmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrta7ubmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pirate-hook" /></template>
