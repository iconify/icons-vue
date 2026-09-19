<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sah62hazp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sah62hazp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-multiple" /></template>
