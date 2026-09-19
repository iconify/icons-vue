<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk_c26-lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hk_c26-lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:star" /></template>
