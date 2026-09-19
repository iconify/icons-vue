<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft7_ypb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":480};
const content = `<path class="ft7_ypb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:timer-off" /></template>
