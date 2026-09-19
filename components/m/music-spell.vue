<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_yksccyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_yksccyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:music-spell" /></template>
