<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szpuq9bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="szpuq9bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-up-fill" /></template>
