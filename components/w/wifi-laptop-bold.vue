<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxgd-b81d.css';
import '../../css/m/mxzgrlbhg.css';
import '../../css/f/frbtlhrdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxgd-b81d"/><path class="mxzgrlbhg"/><path class="frbtlhrdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:wifi-laptop-bold" /></template>
