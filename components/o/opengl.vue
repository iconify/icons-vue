<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpvhkib2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cpvhkib2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:opengl" /></template>
