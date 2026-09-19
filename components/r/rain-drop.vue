<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b760q_svr.css';
import '../../css/k/k20av7rgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b760q_svr"/><path class="k20av7rgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rain-drop" /></template>
