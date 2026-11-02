<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scww_2y7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scww_2y7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:x-skew-fill" /></template>
