<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkf605bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkf605bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:tobi" /></template>
