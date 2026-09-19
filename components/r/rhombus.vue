<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u31id3bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u31id3bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rhombus" /></template>
