<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxm5rigwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxm5rigwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:static-guard" /></template>
