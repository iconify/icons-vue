<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2i-2nbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2i-2nbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swirl-string" /></template>
