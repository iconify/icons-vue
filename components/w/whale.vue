<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c2bd161_c.css';
import '../../css/w/w25rgrb9f.css';
import '../../css/i/id02ik75h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="c2bd161_c"/><path class="w25rgrb9f"/><path class="id02ik75h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:whale" /></template>
