<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i64r4w9ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i64r4w9ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-line" /></template>
