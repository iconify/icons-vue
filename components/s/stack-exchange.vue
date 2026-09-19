<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1yw4pb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="t1yw4pb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:stack-exchange" /></template>
