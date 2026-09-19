<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noelakjxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="noelakjxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:umbraco" /></template>
