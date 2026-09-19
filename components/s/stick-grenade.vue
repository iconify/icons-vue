<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy9pxwbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jy9pxwbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stick-grenade" /></template>
