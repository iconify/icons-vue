<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybj_cgbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybj_cgbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shield-x-solid" /></template>
