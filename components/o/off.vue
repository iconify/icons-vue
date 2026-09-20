<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4p4i2bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y4p4i2bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:off" /></template>
