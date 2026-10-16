<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edp4vc3jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":49.2,"height":49.2,"left":19.5,"top":18.3};
const content = `<path class="edp4vc3jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unisoc" /></template>
