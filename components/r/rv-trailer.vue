<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnanw2lxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnanw2lxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:rv-trailer" /></template>
