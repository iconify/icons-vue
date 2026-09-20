<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdmzp8b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdmzp8b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-hexagon" /></template>
