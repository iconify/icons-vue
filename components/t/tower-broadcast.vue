<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os8x0cc1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="os8x0cc1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tower-broadcast" /></template>
