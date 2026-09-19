<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwhib3n2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="hwhib3n2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-full" /></template>
