<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s2-cudgzz.css';
import '../../css/n/nuotczzel.css';
import '../../css/w/wlabr1bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s2-cudgzz wm-k"/><path class="nuotczzel wm-shine"/><path class="wlabr1bst wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:notepad-text" /></template>
