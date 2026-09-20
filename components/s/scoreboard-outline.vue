<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvy86qb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvy86qb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scoreboard-outline" /></template>
