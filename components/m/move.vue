<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyyypdmmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qyyypdmmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:move" /></template>
