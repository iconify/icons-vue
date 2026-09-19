<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnlnjbcmb.css';
import '../../css/p/pt2uzac8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mnlnjbcmb"/><path class="pt2uzac8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:save-image" /></template>
