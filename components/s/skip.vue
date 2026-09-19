<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds7-_hb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ds7-_hb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:skip" /></template>
