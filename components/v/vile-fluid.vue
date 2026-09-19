<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw7mplqgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw7mplqgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vile-fluid" /></template>
