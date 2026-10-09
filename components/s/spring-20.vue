<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ccpfbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o0ccpfbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spring-20" /></template>
