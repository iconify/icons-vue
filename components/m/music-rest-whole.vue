<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxb7qbbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxb7qbbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-rest-whole" /></template>
