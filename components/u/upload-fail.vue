<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc9mvj8qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pc9mvj8qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:upload-fail" /></template>
