<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai8h5-bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ai8h5-bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:return-key" /></template>
