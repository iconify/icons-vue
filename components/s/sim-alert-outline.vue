<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1863fbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1863fbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sim-alert-outline" /></template>
