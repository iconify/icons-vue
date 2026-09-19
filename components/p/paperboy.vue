<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7j0lof8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":720};
const content = `<path class="h7j0lof8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:paperboy" /></template>
