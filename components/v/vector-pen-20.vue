<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxx9g-boz.css';
import '../../css/e/elto8jbuv.css';
import '../../css/d/dysie4bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uxx9g-boz"/><path class="elto8jbuv"/><path class="dysie4bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vector-pen-20" /></template>
