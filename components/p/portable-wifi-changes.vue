<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq457jqzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="cq457jqzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:portable-wifi-changes" /></template>
