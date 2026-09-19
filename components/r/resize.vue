<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir2o0ybbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ir2o0ybbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:resize" /></template>
