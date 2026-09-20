<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp87u6c8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp87u6c8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ray-start-arrow" /></template>
