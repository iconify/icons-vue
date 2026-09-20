<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0yw_i1yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0yw_i1yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:report-line" /></template>
