<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcqspba_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="mcqspba_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:reorder" /></template>
