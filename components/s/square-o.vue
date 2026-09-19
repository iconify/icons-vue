<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqh-8_m-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="zqh-8_m-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:square-o" /></template>
