<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xop17zbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xop17zbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:videocam-off-outline" /></template>
