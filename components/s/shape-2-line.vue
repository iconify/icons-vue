<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl_q4-bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl_q4-bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shape-2-line" /></template>
