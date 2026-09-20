<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6_kpfbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k6_kpfbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-top-right-and-plane-bottom-left" /></template>
