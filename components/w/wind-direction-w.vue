<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiuit_b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1542,"height":1542};
const content = `<path class="xiuit_b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-direction-w" /></template>
