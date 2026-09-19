<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jja48fb-u.css';
import '../../css/e/e99x7cbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="bi12bsetm"><path class="jja48fb-u"/><path class="e99x7cbrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tmux" /></template>
