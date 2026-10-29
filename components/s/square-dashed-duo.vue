<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4cc2sb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4cc2sb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-dashed-duo" /></template>
