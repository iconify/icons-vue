<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8mxwke8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="h8mxwke8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-caret-right" /></template>
