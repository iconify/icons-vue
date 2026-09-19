<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az1q_bbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az1q_bbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:priority-up" /></template>
