<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvt6i0b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="pvt6i0b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waxing-gibbous-4" /></template>
