<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltr91uweb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltr91uweb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-anticlockwise-1-line" /></template>
