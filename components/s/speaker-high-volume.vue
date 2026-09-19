<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eyl3xwb3e.css';
import '../../css/h/h5yvjibqy.css';
import '../../css/l/lstczpj7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="eyl3xwb3e"/><path class="h5yvjibqy"/><path class="lstczpj7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:speaker-high-volume" /></template>
