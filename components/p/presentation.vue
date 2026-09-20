<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn-j5ybui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn-j5ybui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:presentation" /></template>
