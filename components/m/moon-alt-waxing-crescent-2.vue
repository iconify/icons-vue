<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-uxu8b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="t-uxu8b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waxing-crescent-2" /></template>
