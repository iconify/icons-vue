<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfob3ybxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfob3ybxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:search-outlined" /></template>
