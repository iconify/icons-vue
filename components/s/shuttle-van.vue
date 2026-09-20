<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwkp1t3mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hwkp1t3mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:shuttle-van" /></template>
