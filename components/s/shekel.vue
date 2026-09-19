<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcs7_bcpt.css';
import '../../css/k/kvsed47hf.css';
import '../../css/u/uqfhxrrcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bcs7_bcpt"/><path class="kvsed47hf"/><path class="uqfhxrrcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:shekel" /></template>
