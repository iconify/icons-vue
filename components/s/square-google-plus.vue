<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-uyfqi-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a-uyfqi-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-google-plus" /></template>
