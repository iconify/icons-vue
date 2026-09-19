<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfhjt5i0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rfhjt5i0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:spy" /></template>
