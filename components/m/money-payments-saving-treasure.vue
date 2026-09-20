<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm40es_yd.css';
import '../../css/l/ljwietbxp.css';
import '../../css/e/ecbf7mdmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vm40es_yd"/><path class="ljwietbxp"/><path class="ecbf7mdmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:money-payments-saving-treasure" /></template>
