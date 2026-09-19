<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7lynlblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7lynlblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wrapping-star" /></template>
