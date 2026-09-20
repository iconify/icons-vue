<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0x3uabab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g0x3uabab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:table-tennis-solid" /></template>
