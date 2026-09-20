<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5kjf9bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w5kjf9bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:no-image" /></template>
