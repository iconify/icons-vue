<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeo1bj5bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xeo1bj5bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-high-48" /></template>
