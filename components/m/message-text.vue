<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqq3632lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqq3632lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-text" /></template>
