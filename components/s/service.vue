<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unvf2ewqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="unvf2ewqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:service" /></template>
