<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1dgwgbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1dgwgbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:robotic-gripper" /></template>
