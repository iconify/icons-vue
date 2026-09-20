<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a726jb9_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a726jb9_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:radio-on" /></template>
