<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eunpcrb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eunpcrb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:zoom-out" /></template>
