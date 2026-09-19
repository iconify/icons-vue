<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3wp3gbjk.css';
import '../../css/o/opai67bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t3wp3gbjk"/><path class="opai67bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-hex" /></template>
