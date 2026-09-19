<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef-qzd-jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef-qzd-jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smart-camera" /></template>
