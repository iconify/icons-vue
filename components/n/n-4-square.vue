<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8kungbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="j8kungbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:n-4-square" /></template>
