<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbze-cxxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gbze-cxxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nodemon" /></template>
