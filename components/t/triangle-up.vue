<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3x85-t3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="e3x85-t3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:triangle-up" /></template>
