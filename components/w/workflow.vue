<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/relh8ld0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="relh8ld0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:workflow" /></template>
