<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3p9lioqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c3p9lioqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shark-fin" /></template>
