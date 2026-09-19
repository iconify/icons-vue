<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx_8bjlap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jx_8bjlap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:smoking-room" /></template>
