<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzlu_i1rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uzlu_i1rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:pagebreak" /></template>
