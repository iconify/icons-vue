<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax6ykm6hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ax6ykm6hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:program" /></template>
