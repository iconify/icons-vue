<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-0aw-32q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="r-0aw-32q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:toilet" /></template>
