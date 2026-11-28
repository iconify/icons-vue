<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxt4hdcve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pxt4hdcve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:wc-thin" /></template>
