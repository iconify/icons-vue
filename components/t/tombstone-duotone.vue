<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e7jeh7wes.css';
import '../../css/w/wh5qu1bjh.css';
import '../../css/x/x9h1xwfff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e7jeh7wes"/><path class="wh5qu1bjh"/><path class="x9h1xwfff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tombstone-duotone" /></template>
