<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylm14b_5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ylm14b_5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:saber-toothed-cat-head" /></template>
