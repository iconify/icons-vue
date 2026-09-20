<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shmltxb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="shmltxb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vscode" /></template>
