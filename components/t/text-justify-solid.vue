<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmcu5jzif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmcu5jzif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:text-justify-solid" /></template>
