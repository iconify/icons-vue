<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdpx68b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qdpx68b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:netflix" /></template>
