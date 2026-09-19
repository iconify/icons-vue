<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxnvmcz9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cxnvmcz9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:this-side-up" /></template>
