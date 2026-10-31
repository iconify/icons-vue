<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk3qy-tdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk3qy-tdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-round" /></template>
