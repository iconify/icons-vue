<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf66ysvcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qf66ysvcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wrench-filled" /></template>
