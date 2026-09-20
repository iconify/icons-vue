<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrmr4qgcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrmr4qgcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:snort" /></template>
