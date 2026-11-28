<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1sfe70wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1sfe70wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:monitor" /></template>
