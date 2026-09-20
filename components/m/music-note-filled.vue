<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvv8o3bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvv8o3bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note-filled" /></template>
