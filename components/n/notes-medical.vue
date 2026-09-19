<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucv6mt9cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ucv6mt9cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:notes-medical" /></template>
