<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq4l7_blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dq4l7_blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:mic" /></template>
