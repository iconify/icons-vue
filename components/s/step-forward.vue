<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr8tbrt_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr8tbrt_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:step-forward" /></template>
