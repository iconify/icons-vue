<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw8bn4bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iw8bn4bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:oracle" /></template>
