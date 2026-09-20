<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/e/e6pmp0b8v.css';
import '../../css/r/r1dv0f0sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="pr52f_b5y"><circle class="e6pmp0b8v"/><path class="r1dv0f0sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:person" /></template>
