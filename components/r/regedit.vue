<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkt9v7b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rkt9v7b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:regedit" /></template>
