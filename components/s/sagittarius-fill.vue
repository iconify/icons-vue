<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_blc3t9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_blc3t9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sagittarius-fill" /></template>
