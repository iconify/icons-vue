<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz-ym6b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xz-ym6b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:reservation-orders" /></template>
