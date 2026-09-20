<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5me6jn8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l5me6jn8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:palm" /></template>
