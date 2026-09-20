<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz2qli0dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oz2qli0dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:mars-double" /></template>
