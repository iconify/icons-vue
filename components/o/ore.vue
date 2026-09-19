<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl29yxbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rl29yxbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ore" /></template>
