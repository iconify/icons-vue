<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz-gusbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":88,"height":88};
const content = `<path class="dz-gusbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xbox" /></template>
