<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro5yrac-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ro5yrac-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:object" /></template>
