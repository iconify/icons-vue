<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeys6obdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oeys6obdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-4" /></template>
