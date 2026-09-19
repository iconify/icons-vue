<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maosicbit.css';
import '../../css/k/kggl2nbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="maosicbit"/><path class="kggl2nbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-incoming" /></template>
