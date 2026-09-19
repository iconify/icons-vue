<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1u-c7bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="u1u-c7bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:temperature-quarter" /></template>
