<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6c7gbb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6c7gbb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nano-staged" /></template>
