<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhxvgwbwc.css';
import '../../css/r/rs26g1b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vhxvgwbwc"/><path class="rs26g1b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:tornado" /></template>
