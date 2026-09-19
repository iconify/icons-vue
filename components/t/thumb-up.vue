<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaw3mcb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaw3mcb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:thumb-up" /></template>
