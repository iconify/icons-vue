<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4k6xuuyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u4k6xuuyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:psychic-waves" /></template>
