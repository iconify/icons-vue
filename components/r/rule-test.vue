<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2f_gjbjf.css';
import '../../css/i/ikg83ac8f.css';
import '../../css/f/fvmh2ibcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d2f_gjbjf"/><path class="ikg83ac8f"/><path class="fvmh2ibcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-test" /></template>
