<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck3uzqfhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ck3uzqfhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:pen" /></template>
