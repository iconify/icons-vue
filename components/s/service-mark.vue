<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynhhlqb6o.css';
import '../../css/j/jbls2nr5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ynhhlqb6o"/><path class="jbls2nr5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:service-mark" /></template>
