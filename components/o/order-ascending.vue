<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iav3n6ptp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iav3n6ptp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:order-ascending" /></template>
