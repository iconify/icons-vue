<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xay_q6mqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xay_q6mqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:organic-outline" /></template>
