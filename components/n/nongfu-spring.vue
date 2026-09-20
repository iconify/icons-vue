<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8gxregvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1551,"height":1232};
const content = `<path class="r8gxregvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nongfu-spring" /></template>
