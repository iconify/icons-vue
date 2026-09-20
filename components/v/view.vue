<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqj70vbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cqj70vbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:view" /></template>
