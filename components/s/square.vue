<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imu2dnx8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imu2dnx8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square" /></template>
