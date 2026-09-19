<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvw-7lb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="rvw-7lb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-landscape-lock" /></template>
