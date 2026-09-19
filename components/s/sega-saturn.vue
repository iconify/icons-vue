<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk9i22bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk9i22bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sega-saturn" /></template>
