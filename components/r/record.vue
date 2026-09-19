<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se-dpyb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":422,"height":717};
const content = `<path class="se-dpyb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:record" /></template>
