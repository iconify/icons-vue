<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/u/ud9rda.css';
import '../../css/f/f1b6aw.css';
import '../../css/o/oxx-om.css';
import '../../css/t/tbv09e.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-48.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGTfmnxcrY"><path class="c5xdmn ud9rda"/><circle class="f1b6aw"/><path class="c5xdmn oxx-om tbv09e"/></mask></defs><path mask="url(#SVGTfmnxcrY)" class="botfzx"/><path class="c5xdmn gd_4-q tbv09e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-off" /></template>
