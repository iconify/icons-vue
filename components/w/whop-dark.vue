<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_3d0-bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":383.2,"height":196.4};
const content = `<path class="s_3d0-bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:whop-dark" /></template>
