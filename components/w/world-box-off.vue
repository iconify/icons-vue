<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhzm4jban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhzm4jban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:world-box-off" /></template>
