<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzzr1mstp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":222};
const content = `<path class="gzzr1mstp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vercel-light" /></template>
