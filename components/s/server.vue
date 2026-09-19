<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aje1gjofx.css';
import '../../css/x/xur4k61po.css';
import '../../css/w/wtc6rtblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aje1gjofx"/><path class="xur4k61po"/><path class="wtc6rtblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:server" /></template>
