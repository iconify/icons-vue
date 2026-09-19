<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew_ugga8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ew_ugga8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:pig" /></template>
