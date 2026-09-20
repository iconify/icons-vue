<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be1g-y.css';
import '../../css/d/dr9rsw.css';
import '../../css/b/botfzx.css';
import '../../css/d/d-jkxijw.css';
import '../../css/f/fill-to-1.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG1rOeFd0w"><path class="be1g-y"/><circle class="dr9rsw"/></mask></defs><path mask="url(#SVG1rOeFd0w)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-alt-filled" /></template>
