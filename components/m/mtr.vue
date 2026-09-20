<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0rjxf_hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0rjxf_hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mtr" /></template>
