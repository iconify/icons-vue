<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwee6s4xt.css';
import '../../css/g/grkcr9m5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwee6s4xt"/><path class="grkcr9m5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ruler-20-bold" /></template>
