<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw4zn3u8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw4zn3u8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-4-3-bulk-round" /></template>
