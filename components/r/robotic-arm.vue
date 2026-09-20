<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi8vzbbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qi8vzbbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:robotic-arm" /></template>
