<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkefbw.css';
import '../../css/t/t5pxry.css';
import '../../css/d/dr9rsw.css';
import '../../css/o/oxx-om.css';
import '../../css/x/x1bqbh.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/d/d-jkxijw.css';
import '../../css/f/fill-to-1.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGDMme5c7q"><path class="rkefbw t5pxry"/><circle class="dr9rsw"/><path class="oxx-om t5pxry x1bqbh"/></mask></defs><path mask="url(#SVGDMme5c7q)" class="botfzx"/><path class="gd_4-q t5pxry x1bqbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-alt-off-filled" /></template>
