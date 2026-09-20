<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkzz6m3te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkzz6m3te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:shield" /></template>
