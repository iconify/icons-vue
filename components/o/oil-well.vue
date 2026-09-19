<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp8hlbcad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vp8hlbcad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:oil-well" /></template>
