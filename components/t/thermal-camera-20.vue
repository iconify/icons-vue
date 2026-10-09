<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ehq2mog.css';
import '../../css/i/ij_095b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l9ehq2mog"/><path class="ij_095b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-camera-20" /></template>
