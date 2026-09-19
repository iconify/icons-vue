<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crncvzb-e.css';
import '../../css/t/tn0_q5b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="crncvzb-e"/><circle class="tn0_q5b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:notification-counter" /></template>
