<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz8on2utd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz8on2utd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-check" /></template>
