<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu9si2flt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu9si2flt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-play-light" /></template>
