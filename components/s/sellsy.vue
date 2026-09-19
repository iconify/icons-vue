<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnmhnfnsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="rnmhnfnsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:sellsy" /></template>
