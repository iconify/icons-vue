<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx2s7v57f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx2s7v57f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pantone-fill" /></template>
