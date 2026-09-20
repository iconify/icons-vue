<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7jdwou_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7jdwou_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-pos-wrench-outline" /></template>
