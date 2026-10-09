<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6edurbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c6edurbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-low-20" /></template>
