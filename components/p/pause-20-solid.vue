<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey5-szfvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ey5-szfvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pause-20-solid" /></template>
