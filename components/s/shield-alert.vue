<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryhcp-7eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ryhcp-7eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shield-alert" /></template>
