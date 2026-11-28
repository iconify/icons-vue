<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyau2rryt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyau2rryt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ping-pong" /></template>
