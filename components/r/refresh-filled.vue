<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc2f8fcca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc2f8fcca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:refresh-filled" /></template>
