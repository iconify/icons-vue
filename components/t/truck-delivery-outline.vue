<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ren4p7bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ren4p7bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-delivery-outline" /></template>
