<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swz-qybok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="swz-qybok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waning-crescent-3" /></template>
