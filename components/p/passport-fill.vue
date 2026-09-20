<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd789zbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd789zbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:passport-fill" /></template>
