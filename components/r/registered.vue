<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrrd32akn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrrd32akn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:registered" /></template>
