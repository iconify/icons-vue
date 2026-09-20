<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1m2x9bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j1m2x9bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:vue" /></template>
