<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0vyxlb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":508,"height":512};
const content = `<path class="y0vyxlb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:vagrant" /></template>
