<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrx-36bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrx-36bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-square-error" /></template>
