<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzezueapn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jzezueapn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:thumbnails" /></template>
