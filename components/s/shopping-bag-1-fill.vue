<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4j9ipb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4j9ipb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shopping-bag-1-fill" /></template>
