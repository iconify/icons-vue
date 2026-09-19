<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugjzi838y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugjzi838y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:suitcase" /></template>
