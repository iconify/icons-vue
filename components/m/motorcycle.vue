<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msb5m1bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="msb5m1bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:motorcycle" /></template>
