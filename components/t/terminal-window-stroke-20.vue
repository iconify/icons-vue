<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afub65bxw.css';
import '../../css/k/kfsq47nik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="afub65bxw"/><path class="kfsq47nik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-window-stroke-20" /></template>
