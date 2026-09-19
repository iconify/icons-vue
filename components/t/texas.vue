<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9j73r6gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9j73r6gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:texas" /></template>
