<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln3ktcb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ln3ktcb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-off-20" /></template>
