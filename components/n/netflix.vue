<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj_a3_b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj_a3_b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:netflix" /></template>
