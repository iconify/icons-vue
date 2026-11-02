<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo2s3r1kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo2s3r1kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sleigh-line" /></template>
