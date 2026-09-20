<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwtwdjbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwtwdjbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wind2" /></template>
