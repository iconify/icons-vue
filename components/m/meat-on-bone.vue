<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sobp7ui6c.css';
import '../../css/q/q6antebxy.css';
import '../../css/y/yp73vgbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sobp7ui6c"/><path class="q6antebxy"/><path class="yp73vgbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:meat-on-bone" /></template>
