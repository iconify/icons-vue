<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-pp4uinw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-pp4uinw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-arrow-right" /></template>
