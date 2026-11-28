<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh0izzb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh0izzb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-info-solid" /></template>
