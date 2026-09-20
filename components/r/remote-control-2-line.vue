<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el-2dqbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el-2dqbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:remote-control-2-line" /></template>
