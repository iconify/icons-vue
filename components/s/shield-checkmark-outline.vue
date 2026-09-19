<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0ful6buz.css';
import '../../css/i/iy-sd1yvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y0ful6buz"/><path class="iy-sd1yvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shield-checkmark-outline" /></template>
