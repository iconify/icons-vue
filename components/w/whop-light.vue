<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_hnosb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":383.2,"height":196.4};
const content = `<path class="l_hnosb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:whop-light" /></template>
