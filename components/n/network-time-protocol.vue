<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zilrarrlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zilrarrlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-time-protocol" /></template>
