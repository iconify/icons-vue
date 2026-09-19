<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3c_78bkn.css';
import '../../css/v/v758r-tyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v3c_78bkn"/><path class="v758r-tyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:shrink-screen" /></template>
