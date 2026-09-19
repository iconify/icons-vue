<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sje80lrlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sje80lrlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:radial-balance" /></template>
