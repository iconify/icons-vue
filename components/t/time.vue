<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdaz6f6ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="zdaz6f6ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:time" /></template>
