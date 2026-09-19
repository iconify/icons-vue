<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt5up1vxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qt5up1vxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:software-resource-resource" /></template>
