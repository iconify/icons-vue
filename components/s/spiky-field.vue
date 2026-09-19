<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfpx3bbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfpx3bbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiky-field" /></template>
