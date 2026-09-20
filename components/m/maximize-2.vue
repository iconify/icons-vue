<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc1erobyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc1erobyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:maximize-2" /></template>
