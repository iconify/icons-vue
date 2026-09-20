<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fib1smptu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fib1smptu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sun-schedule-outline" /></template>
