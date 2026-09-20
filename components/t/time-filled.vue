<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmb0t7bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmb0t7bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:time-filled" /></template>
