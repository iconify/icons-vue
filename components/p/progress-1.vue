<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh8kj0bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="nh8kj0bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-1" /></template>
