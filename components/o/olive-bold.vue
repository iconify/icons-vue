<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kohl8lpdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kohl8lpdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:olive-bold" /></template>
