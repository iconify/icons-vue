<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2smc50-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="m2smc50-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:time-12" /></template>
