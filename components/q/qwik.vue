<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s53vmbcgz.css';
import '../../css/j/jick4kgxj.css';
import '../../css/b/bxyjj4o7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="s53vmbcgz"><path class="jick4kgxj"/><path class="bxyjj4o7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:qwik" /></template>
