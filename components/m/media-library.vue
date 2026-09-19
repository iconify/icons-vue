<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-01x7gco.css';
import '../../css/e/e2rfzjbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t-01x7gco"/><path class="e2rfzjbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:media-library" /></template>
