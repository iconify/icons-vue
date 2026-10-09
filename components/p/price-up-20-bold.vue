<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt6n36bom.css';
import '../../css/i/i5jbbacbv.css';
import '../../css/e/egl9w0p1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gt6n36bom"/><path class="i5jbbacbv"/><path class="egl9w0p1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-up-20-bold" /></template>
