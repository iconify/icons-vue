<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpehaf3is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qpehaf3is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-bus" /></template>
