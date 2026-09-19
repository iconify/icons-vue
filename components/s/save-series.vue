<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnlnjbcmb.css';
import '../../css/o/ozxr3zrwe.css';
import '../../css/j/j-_c-dbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mnlnjbcmb"/><path class="ozxr3zrwe"/><path class="j-_c-dbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:save-series" /></template>
