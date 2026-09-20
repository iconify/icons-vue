<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3jlfq7fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="v3jlfq7fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-waxing-crescent-4" /></template>
