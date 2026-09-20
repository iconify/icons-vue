<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikzuh16qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ikzuh16qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:travel-bus" /></template>
