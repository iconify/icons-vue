<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfhguzbcb.css';
import '../../css/f/f_mc5ezfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jfhguzbcb"/><path class="f_mc5ezfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sway" /></template>
