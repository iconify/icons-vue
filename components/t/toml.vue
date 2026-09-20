<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm5-86ulh.css';
import '../../css/e/e_r59eb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fm5-86ulh"/><path class="e_r59eb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:toml" /></template>
