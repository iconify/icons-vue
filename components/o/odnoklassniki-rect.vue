<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qza9p6emh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="qza9p6emh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:odnoklassniki-rect" /></template>
