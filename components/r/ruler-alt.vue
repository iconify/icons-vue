<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo997g_ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zo997g_ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ruler-alt" /></template>
