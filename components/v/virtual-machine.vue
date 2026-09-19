<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q73ykcblb.css';
import '../../css/q/qgekv_ybn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q73ykcblb"/><path class="qgekv_ybn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:virtual-machine" /></template>
