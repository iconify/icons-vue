<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se5j6sb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="se5j6sb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:order-stratus" /></template>
