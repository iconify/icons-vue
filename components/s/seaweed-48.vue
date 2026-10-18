<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o60fd0ylo.css';
import '../../css/n/najn_bcni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o60fd0ylo"/><path class="najn_bcni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seaweed-48" /></template>
