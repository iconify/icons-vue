<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmtf56boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jmtf56boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:star-stroked" /></template>
