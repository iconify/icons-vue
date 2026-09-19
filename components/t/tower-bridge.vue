<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrx28bc2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrx28bc2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tower-bridge" /></template>
