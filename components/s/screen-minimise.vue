<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evkjnzbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="evkjnzbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:screen-minimise" /></template>
