<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntcvex3pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntcvex3pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vip-crown-line" /></template>
