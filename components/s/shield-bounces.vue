<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl1w99b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jl1w99b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shield-bounces" /></template>
