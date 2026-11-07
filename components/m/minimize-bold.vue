<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-sogubpk.css';
import '../../css/k/kob3fcbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-sogubpk"/><path class="kob3fcbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-bold" /></template>
