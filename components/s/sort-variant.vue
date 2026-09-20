<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx1dusbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx1dusbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-variant" /></template>
