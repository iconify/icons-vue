<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5jdxi8fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5jdxi8fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:virus" /></template>
