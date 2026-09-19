<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6vi1xb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="n6vi1xb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:star" /></template>
