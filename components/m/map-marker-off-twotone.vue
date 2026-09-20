<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkymbu.css';
import '../../css/g/g26hbu.css';
import '../../css/t/t5pxry.css';
import '../../css/x/xopa8c.css';
import '../../css/j/jnqe1f.css';
import '../../css/o/oxx-om.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-48.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGRzINhd9p"><path class="dkymbu g26hbu t5pxry"/><circle class="g26hbu xopa8c"/><path class="jnqe1f oxx-om t5pxry"/></mask></defs><path mask="url(#SVGRzINhd9p)" class="botfzx"/><path class="gd_4-q jnqe1f t5pxry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-off-twotone" /></template>
