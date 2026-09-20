<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_e6p9bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w_e6p9bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:thermometer-quarter-solid" /></template>
