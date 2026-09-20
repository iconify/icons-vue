<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un82f_hcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un82f_hcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notification-line" /></template>
