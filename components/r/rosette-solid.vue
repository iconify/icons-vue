<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh_mdjk1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh_mdjk1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rosette-solid" /></template>
