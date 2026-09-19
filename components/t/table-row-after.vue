<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozn60lppr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ozn60lppr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:table-row-after" /></template>
