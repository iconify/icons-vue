<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0lofkbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0lofkbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-strike-stroke-20" /></template>
