<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_x0gwbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_x0gwbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:robot-vacuum-check" /></template>
