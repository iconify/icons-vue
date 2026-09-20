<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkx-71q0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkx-71q0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:testcafe" /></template>
