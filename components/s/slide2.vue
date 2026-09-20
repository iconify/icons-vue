<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyis771pa.css';
import '../../css/k/kfc9attts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pyis771pa"/><path class="kfc9attts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:slide2" /></template>
