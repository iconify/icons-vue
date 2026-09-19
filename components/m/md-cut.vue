<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t41vinb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t41vinb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-cut" /></template>
