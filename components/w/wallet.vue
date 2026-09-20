<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6uiwabmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g6uiwabmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:wallet" /></template>
