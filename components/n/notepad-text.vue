<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mi-mpqbpu.css';
import '../../css/i/il17kbbxg.css';
import '../../css/e/ehq3u9bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mi-mpqbpu"/><rect class="il17kbbxg"/><path class="ehq3u9bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:notepad-text" /></template>
