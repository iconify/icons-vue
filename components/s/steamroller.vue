<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxt0y0-yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxt0y0-yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:steamroller" /></template>
