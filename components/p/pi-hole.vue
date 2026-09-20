<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxr1szbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxr1szbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pi-hole" /></template>
