<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjtn95y0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjtn95y0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-3-bold" /></template>
