<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r95dy2bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r95dy2bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:stopwatch" /></template>
