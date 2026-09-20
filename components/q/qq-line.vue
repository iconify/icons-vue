<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldv-uvbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldv-uvbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qq-line" /></template>
