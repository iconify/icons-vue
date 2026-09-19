<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a04lmzz9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a04lmzz9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pentagon-left-solid" /></template>
