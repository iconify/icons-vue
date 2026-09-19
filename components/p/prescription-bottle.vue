<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njk0u4giu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="njk0u4giu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:prescription-bottle" /></template>
