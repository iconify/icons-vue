<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2i76-b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":32};
const content = `<path class="r2i76-b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:streetsign" /></template>
