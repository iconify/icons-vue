<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tof6bnmuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tof6bnmuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:toggle" /></template>
