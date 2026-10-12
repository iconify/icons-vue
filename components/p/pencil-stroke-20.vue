<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3fa6r4bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q3fa6r4bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pencil-stroke-20" /></template>
