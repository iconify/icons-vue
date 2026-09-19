<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htglb-b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="htglb-b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sketchup-layout" /></template>
