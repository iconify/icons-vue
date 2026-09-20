<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d488w9blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d488w9blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2013-light" /></template>
