<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d48o06bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="d48o06bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:resize-full" /></template>
