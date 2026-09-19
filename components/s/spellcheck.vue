<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd37n7bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":416};
const content = `<path class="kd37n7bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:spellcheck" /></template>
