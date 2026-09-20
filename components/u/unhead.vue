<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p4cak4b3x.css';
import '../../css/h/hydipxqed.css';
import '../../css/m/mk4tyejxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p4cak4b3x"/><path class="hydipxqed"/><path class="mk4tyejxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="unjs:unhead" /></template>
