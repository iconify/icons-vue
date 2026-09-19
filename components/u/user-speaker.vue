<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln8kehb4v.css';
import '../../css/h/hz4g9vbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ln8kehb4v"/><path class="hz4g9vbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-speaker" /></template>
