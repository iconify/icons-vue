<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/o/olch4qxxi.css';
import '../../css/b/b5ffqpx6z.css';
import '../../css/r/r3j1v0bfk.css';
import '../../css/n/n9khbr3yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="olch4qxxi wm-shadow"/><path class="b5ffqpx6z wm-shadow"/><path class="r3j1v0bfk"/><path class="n9khbr3yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:more-horizontal" /></template>
