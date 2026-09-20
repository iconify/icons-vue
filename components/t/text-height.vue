<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_6-kgpqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y_6-kgpqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:text-height" /></template>
