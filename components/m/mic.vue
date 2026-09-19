<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmets6kjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cmets6kjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:mic" /></template>
