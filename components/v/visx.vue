<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blz_a82jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blz_a82jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:visx" /></template>
