<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekdmi3b6m.css';
import '../../css/l/l3_41-7cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ekdmi3b6m"/><path class="l3_41-7cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-smartphone-pay-dollar" /></template>
