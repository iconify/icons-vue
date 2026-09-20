<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr78b8bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr78b8bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pavilion-line" /></template>
