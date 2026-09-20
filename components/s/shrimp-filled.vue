<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgrkjrbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgrkjrbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shrimp-filled" /></template>
