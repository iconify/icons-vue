<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuij3-bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iuij3-bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:roots" /></template>
