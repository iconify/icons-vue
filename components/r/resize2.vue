<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqten3byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqten3byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:resize2" /></template>
