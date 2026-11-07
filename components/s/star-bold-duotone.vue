<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kka22lbso.css';
import '../../css/u/u0y1r5zna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kka22lbso"/><path class="u0y1r5zna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-bold-duotone" /></template>
