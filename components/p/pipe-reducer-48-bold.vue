<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvlu12bfl.css';
import '../../css/k/kqfh3ccjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvlu12bfl"/><path class="kqfh3ccjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-reducer-48-bold" /></template>
