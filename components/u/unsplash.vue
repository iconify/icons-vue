<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw6pplx8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yw6pplx8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:unsplash" /></template>
