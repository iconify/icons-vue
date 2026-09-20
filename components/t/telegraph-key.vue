<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew4hn1bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ew4hn1bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:telegraph-key" /></template>
