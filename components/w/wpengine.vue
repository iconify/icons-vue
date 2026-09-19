<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8io2hbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e8io2hbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:wpengine" /></template>
