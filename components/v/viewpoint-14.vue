<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncwxpd7_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ncwxpd7_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:viewpoint-14" /></template>
