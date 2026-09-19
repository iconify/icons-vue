<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3nyc0bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="z3nyc0bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:space-shuttle" /></template>
