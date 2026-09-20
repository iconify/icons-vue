<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3vmni1om.css';
import '../../css/i/i_h7t1znx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3vmni1om"/><path class="i_h7t1znx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:microchip-board-bold" /></template>
