<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwx5d7bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwx5d7bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:page-last" /></template>
