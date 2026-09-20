<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l37jp9bzw.css';
import '../../css/t/t54c4pnar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l37jp9bzw"/><path class="t54c4pnar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tower-clock-filled" /></template>
