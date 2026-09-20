<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy42w6b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy42w6b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pause-circle-stroke-filled" /></template>
