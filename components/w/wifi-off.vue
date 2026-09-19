<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vljw1kbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":504,"height":440};
const content = `<path class="vljw1kbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wifi-off" /></template>
