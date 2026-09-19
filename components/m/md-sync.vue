<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht297tb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ht297tb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-sync" /></template>
