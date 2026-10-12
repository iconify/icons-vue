<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxjg9cssi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kxjg9cssi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:puzzle-piece-stroke-20" /></template>
