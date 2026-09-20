<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow_mhd47z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ow_mhd47z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:spray-can-solid" /></template>
