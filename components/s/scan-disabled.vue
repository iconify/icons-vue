<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btq7sccff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="btq7sccff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scan-disabled" /></template>
