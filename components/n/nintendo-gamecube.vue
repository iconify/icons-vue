<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlp2d-pxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tlp2d-pxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:nintendo-gamecube" /></template>
