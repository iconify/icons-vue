<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofo5cbhew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ofo5cbhew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waxing-gibbous-3" /></template>
