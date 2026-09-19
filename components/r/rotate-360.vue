<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whars2o0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="whars2o0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rotate-360" /></template>
