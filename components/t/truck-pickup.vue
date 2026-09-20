<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paa52gbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="paa52gbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:truck-pickup" /></template>
