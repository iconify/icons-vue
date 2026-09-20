<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9kk59e6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9kk59e6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:yammer" /></template>
