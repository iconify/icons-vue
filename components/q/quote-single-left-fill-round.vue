<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9-vbfqmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9-vbfqmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-single-left-fill-round" /></template>
