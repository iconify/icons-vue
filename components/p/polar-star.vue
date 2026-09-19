<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2x-0cbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2x-0cbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:polar-star" /></template>
