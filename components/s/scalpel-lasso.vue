<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8pdp68ro.css';
import '../../css/t/t-wcwabfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w8pdp68ro"/><path class="t-wcwabfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scalpel-lasso" /></template>
