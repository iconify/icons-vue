<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj4pe0big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":264.6,"height":255.6};
const content = `<path class="sj4pe0big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nestjs" /></template>
