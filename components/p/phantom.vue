<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdxsx2lpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdxsx2lpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:phantom" /></template>
