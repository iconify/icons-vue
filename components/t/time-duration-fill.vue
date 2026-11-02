<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l32j6t-3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l32j6t-3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:time-duration-fill" /></template>
