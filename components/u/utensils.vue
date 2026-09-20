<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmr23pb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cmr23pb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:utensils" /></template>
