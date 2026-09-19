<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2hyn8xrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o2hyn8xrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:slickpic" /></template>
