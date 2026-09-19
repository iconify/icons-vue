<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnhs46brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pnhs46brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tornado" /></template>
