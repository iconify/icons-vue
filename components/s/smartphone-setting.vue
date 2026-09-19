<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouy_cybgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="ouy_cybgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-setting" /></template>
