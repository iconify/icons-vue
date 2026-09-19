<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsyu_vb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xsyu_vb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:refrigerant" /></template>
