<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clyii8_rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":544,"height":512};
const content = `<path class="clyii8_rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:medrt" /></template>
