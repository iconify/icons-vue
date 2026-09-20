<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3ppv4bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e3ppv4bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:taxi" /></template>
