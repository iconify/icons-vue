<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppq8x2-2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ppq8x2-2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rectangle-ad" /></template>
