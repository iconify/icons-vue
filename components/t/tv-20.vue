<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrgo4ebxh.css';
import '../../css/s/s0l3_tbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vrgo4ebxh"/><path class="s0l3_tbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tv-20" /></template>
