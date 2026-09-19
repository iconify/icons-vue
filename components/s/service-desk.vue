<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x63-purll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x63-purll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:service-desk" /></template>
