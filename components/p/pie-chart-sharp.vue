<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sit0q75hg.css';
import '../../css/a/ajb1qznwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sit0q75hg"/><path class="ajb1qznwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pie-chart-sharp" /></template>
