<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_m11lbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_m11lbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:webdotde" /></template>
