<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdmajab3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gdmajab3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:shelter-14" /></template>
