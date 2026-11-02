<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywdt5hb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywdt5hb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sound-line-line" /></template>
