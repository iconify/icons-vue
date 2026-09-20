<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me00cjb6q.css';
import '../../css/r/r4-esbb-w.css';
import '../../css/y/yq5xc3f-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="me00cjb6q"/><path class="r4-esbb-w"/><path class="yq5xc3f-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:python-misc" /></template>
