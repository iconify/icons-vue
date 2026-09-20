<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdjxh7b1z.css';
import '../../css/u/utq4fcbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdjxh7b1z"/><path class="utq4fcbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:road-tunnel-bold" /></template>
