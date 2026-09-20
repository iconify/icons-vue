<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr6lp2beq.css';
import '../../css/m/m74onmbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zr6lp2beq"/><path class="m74onmbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phpsysinfo-light" /></template>
