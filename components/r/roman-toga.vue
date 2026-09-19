<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-r4kwbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-r4kwbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:roman-toga" /></template>
