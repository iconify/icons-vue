<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn5ch7ksf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn5ch7ksf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thermometer" /></template>
