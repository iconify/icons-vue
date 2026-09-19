<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8_nnsy-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i8_nnsy-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:plus-alt" /></template>
