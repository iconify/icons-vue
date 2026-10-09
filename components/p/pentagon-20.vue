<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipdcptb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ipdcptb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pentagon-20" /></template>
