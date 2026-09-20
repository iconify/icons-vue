<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbizracty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="hbizracty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waxing-crescent-4" /></template>
