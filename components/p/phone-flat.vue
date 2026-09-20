<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb3zijiqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rb3zijiqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:phone-flat" /></template>
