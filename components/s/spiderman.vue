<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxh8cdbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":835,"height":1024};
const content = `<path class="fxh8cdbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:spiderman" /></template>
