<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8893zazi.css';
import '../../css/k/k-2_-zb2s.css';
import '../../css/a/aw-an9zor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x8893zazi"/><path class="k-2_-zb2s"/><path class="aw-an9zor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:outlook-severe" /></template>
