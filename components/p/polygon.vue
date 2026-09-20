<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr_kw94ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zr_kw94ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:polygon" /></template>
