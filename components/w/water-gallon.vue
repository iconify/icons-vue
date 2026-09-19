<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwze480gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwze480gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-gallon" /></template>
