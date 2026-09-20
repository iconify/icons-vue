<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzephrjzr.css';
import '../../css/q/qpinueb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pzephrjzr"/><path class="qpinueb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-picture-polaroid" /></template>
