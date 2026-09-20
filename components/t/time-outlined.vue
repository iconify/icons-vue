<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwsdxebrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwsdxebrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:time-outlined" /></template>
