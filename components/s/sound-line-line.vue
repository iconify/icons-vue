<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icu2hnb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icu2hnb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sound-line-line" /></template>
