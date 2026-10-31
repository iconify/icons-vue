<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/ur3vzyb7h.css';
import '../../css/n/ndo8e3jvz.css';
import '../../css/j/jty3hzbzs.css';
import '../../css/c/c3_i8_3rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ur3vzyb7h wm-shadow"/><path class="ndo8e3jvz wm-shadow"/><path class="jty3hzbzs"/><path class="c3_i8_3rt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:menu" /></template>
