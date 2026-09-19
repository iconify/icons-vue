<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqzy1o9tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqzy1o9tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:steampunk-goggles" /></template>
