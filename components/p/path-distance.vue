<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nur936bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nur936bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:path-distance" /></template>
