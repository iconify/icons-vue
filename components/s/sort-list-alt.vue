<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l7ux1bcwo.css';
import '../../css/b/brsegwbww.css';
import '../../css/d/djuzueg0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l7ux1bcwo"/><path class="brsegwbww"/><path class="djuzueg0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sort-list-alt" /></template>
