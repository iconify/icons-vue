<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3kirm1i.css';
import '../../css/n/n5821were.css';
import '../../css/z/zwvmvgb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pc3kirm1i"/><path class="n5821were"/><path class="zwvmvgb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:scroll-down" /></template>
