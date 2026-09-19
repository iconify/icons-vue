<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-f499btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b-f499btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature" /></template>
