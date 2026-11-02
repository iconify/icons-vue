<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxnts5b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxnts5b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-add-2-fill" /></template>
