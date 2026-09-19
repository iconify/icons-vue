<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_v7n7b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_v7n7b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:target-dummy" /></template>
