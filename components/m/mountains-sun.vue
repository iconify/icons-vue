<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqt44cdfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqt44cdfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:mountains-sun" /></template>
