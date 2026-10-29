<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r-nxp722e.css';
import '../../css/c/c9t42sbli.css';
import '../../css/t/t2177ccar.css';
import '../../css/h/hsjegpbhu.css';
import '../../css/i/iwm6coyho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="r-nxp722e"/><path class="c9t42sbli wm-a"/><path class="t2177ccar wm-s"/><path class="hsjegpbhu"/><path class="iwm6coyho wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:teapot" /></template>
