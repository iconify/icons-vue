<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umbjv2blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="umbjv2blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:peaks" /></template>
