<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5lux2bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t5lux2bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:modtri" /></template>
