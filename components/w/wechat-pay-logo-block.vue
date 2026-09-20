<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe24tacqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qe24tacqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wechat-pay-logo-block" /></template>
