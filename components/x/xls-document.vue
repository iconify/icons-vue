<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5yf_0fyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a5yf_0fyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:xls-document" /></template>
