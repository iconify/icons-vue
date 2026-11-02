<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf557bbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf557bbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-dashed-fill" /></template>
