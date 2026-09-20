<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndg28nbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ndg28nbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sass" /></template>
