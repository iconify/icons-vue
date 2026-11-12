<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt4l2gbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt4l2gbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tasmocompiler-dark" /></template>
