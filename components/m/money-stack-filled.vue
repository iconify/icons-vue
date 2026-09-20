<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddwhyr-dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddwhyr-dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:money-stack-filled" /></template>
