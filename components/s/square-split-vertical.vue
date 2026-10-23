<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw9fhgbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw9fhgbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-split-vertical" /></template>
