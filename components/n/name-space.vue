<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw30pt-nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gw30pt-nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:name-space" /></template>
