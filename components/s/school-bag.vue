<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_t0vpb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_t0vpb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:school-bag" /></template>
