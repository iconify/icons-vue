<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuuzw8blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuuzw8blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:music-room" /></template>
