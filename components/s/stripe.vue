<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5be5-ssr.css';
import '../../css/u/u8j5knbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e5be5-ssr"/><path class="u8j5knbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:stripe" /></template>
