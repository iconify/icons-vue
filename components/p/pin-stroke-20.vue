<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxjqwnk_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nxjqwnk_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pin-stroke-20" /></template>
