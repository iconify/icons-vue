<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyt5j2bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tyt5j2bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:schematics" /></template>
