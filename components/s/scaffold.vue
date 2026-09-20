<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg8v-pb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yg8v-pb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:scaffold" /></template>
