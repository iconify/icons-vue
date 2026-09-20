<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm_q50s4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm_q50s4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:u-turn-left-bold" /></template>
