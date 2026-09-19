<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtr2n8b0s.css';
import '../../css/o/o9scry_ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtr2n8b0s"/><path class="o9scry_ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:movie-play" /></template>
