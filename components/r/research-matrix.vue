<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozprgdw2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ozprgdw2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:research-matrix" /></template>
