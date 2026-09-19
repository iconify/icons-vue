<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so3-zcgst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="so3-zcgst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rocket-thruster" /></template>
