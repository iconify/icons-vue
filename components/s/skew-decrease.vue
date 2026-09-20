<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f96_kccde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f96_kccde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skew-decrease" /></template>
