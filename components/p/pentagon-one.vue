<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emsq_7iza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="emsq_7iza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pentagon-one" /></template>
