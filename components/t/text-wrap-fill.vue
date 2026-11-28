<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otd380onp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="otd380onp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-wrap-fill" /></template>
