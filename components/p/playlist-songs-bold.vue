<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2ub02obh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ub02obh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:playlist-songs-bold" /></template>
