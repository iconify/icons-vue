<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-bv_67hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="e-bv_67hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pencil" /></template>
