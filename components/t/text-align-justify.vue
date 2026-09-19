<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqu8cgb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqu8cgb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-align-justify" /></template>
