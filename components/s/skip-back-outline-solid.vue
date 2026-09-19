<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogsihlbkj.css';
import '../../css/s/svdy80z7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ogsihlbkj"/><path class="svdy80z7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:skip-back-outline-solid" /></template>
