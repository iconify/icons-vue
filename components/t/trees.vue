<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhsf18bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhsf18bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:trees" /></template>
