<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebc7d1mqz.css';
import '../../css/j/j4kat4bzg.css';
import '../../css/o/oh9bdxpde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ebc7d1mqz"/><path class="j4kat4bzg"/><path class="oh9bdxpde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-loading-box" /></template>
