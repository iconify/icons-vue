<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx936jb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx936jb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:movie-play-filled" /></template>
