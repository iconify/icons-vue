<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf203d6op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pf203d6op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thumb-down" /></template>
