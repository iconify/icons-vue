<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u834x3b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u834x3b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-next-light" /></template>
