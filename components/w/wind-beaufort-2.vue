<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeg_jyl6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="xeg_jyl6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-2" /></template>
