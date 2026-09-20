<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd6wl4g4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd6wl4g4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mouse-fill" /></template>
