<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz5xi_b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cz5xi_b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:renew" /></template>
