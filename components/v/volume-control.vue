<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2v34pbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g2v34pbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:volume-control" /></template>
