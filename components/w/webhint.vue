<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu6aho1hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":120};
const content = `<path class="vu6aho1hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:webhint" /></template>
