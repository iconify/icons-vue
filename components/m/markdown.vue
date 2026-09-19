<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9g2v966j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l9g2v966j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:markdown" /></template>
