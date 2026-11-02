<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg1q8-kvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg1q8-kvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:umbrella-2-line" /></template>
