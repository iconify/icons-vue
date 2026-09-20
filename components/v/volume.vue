<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy_y1766j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xy_y1766j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume" /></template>
