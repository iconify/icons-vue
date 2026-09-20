<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjcaekbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjcaekbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:test-tube-filled-line" /></template>
