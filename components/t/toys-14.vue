<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq9zdxefn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lq9zdxefn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:toys-14" /></template>
