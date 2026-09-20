<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm_q1n7-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm_q1n7-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-pause" /></template>
