<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub56r4xjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ub56r4xjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spy" /></template>
