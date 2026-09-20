<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gic1lptei.css';
import '../../css/r/ro345yboz.css';
import '../../css/j/jb6rr0b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gic1lptei"><path class="ro345yboz"/><path class="jb6rr0b4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:player2" /></template>
