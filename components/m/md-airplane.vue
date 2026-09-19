<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta3mn9bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ta3mn9bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-airplane" /></template>
