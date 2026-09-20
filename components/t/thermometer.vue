<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lswb97b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lswb97b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:thermometer" /></template>
