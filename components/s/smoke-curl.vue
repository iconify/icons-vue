<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr_i2abbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nr_i2abbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:smoke-curl" /></template>
