<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwvyjkl5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwvyjkl5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:round-table" /></template>
