<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfd1wccdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kfd1wccdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:swim" /></template>
