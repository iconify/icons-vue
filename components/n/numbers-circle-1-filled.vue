<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv_r-fwua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv_r-fwua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-circle-1-filled" /></template>
