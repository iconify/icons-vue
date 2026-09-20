<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-hwp71hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-hwp71hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:train-diesel" /></template>
