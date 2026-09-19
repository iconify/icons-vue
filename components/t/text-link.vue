<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe4vwfu9e.css';
import '../../css/d/d8r3yjb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xe4vwfu9e"/><path class="d8r3yjb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-link" /></template>
