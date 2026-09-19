<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt3dg-b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1280};
const content = `<path class="xt3dg-b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:twitter" /></template>
