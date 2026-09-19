<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx1pw_-qf.css';
import '../../css/g/g5xqtsbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="SVGmEns5cJB" class="nx1pw_-qf"/></defs><use href="#SVGmEns5cJB"/><use href="#SVGmEns5cJB"/><path class="g5xqtsbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:new-tab" /></template>
