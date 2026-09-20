<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq_w9hbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq_w9hbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mxc" /></template>
