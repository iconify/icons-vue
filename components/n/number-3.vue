<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqm51mwuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jqm51mwuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-3" /></template>
