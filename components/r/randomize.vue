<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2k_bn38y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k2k_bn38y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:randomize" /></template>
