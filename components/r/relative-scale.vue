<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj4ymt_rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wj4ymt_rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:relative-scale" /></template>
