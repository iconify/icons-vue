<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/senz0-dsw.css';
import '../../css/b/bwz9z8l8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="senz0-dsw"/><path class="bwz9z8l8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:slint" /></template>
