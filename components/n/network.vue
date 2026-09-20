<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x90scwbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x90scwbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:network" /></template>
