<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-wun9brn.css';
import '../../css/l/libay-4ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c-wun9brn"/><path class="libay-4ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-x-ray" /></template>
