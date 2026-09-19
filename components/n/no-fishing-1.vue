<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrkdgzw8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrkdgzw8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-fishing-1" /></template>
