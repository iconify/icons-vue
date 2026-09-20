<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z79qiog2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z79qiog2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:progress-check" /></template>
