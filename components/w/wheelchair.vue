<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmdu-abxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cmdu-abxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:wheelchair" /></template>
