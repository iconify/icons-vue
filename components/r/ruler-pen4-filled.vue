<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvb-mac4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvb-mac4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ruler-pen4-filled" /></template>
