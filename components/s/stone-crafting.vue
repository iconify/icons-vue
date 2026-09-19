<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_rvogbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_rvogbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stone-crafting" /></template>
