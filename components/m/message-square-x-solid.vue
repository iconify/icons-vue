<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybm3768ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybm3768ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-x-solid" /></template>
