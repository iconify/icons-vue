<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo3u2eb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo3u2eb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:view-compact-line" /></template>
