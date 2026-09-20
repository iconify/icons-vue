<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikpmeqhhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikpmeqhhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:record-audio" /></template>
