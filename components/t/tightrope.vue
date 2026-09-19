<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq9u-lbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lq9u-lbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tightrope" /></template>
