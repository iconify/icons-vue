<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytk1r_97s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytk1r_97s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:plus" /></template>
