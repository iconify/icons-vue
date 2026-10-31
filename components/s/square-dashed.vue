<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/byy6wdbxw.css';
import '../../css/u/uo7v-mbdc.css';
import '../../css/e/e349cfoaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="byy6wdbxw wm-shadow"/><path class="uo7v-mbdc wm-shadow"/><path class="e349cfoaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:square-dashed" /></template>
